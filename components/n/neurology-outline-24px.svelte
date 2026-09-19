<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2hne7ojo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2hne7ojo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:neurology-outline-24px" {...props}></Icon>
