<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csk3q3blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="csk3q3blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notes-outline" {...props}></Icon>
