<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry15pac0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ry15pac0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-outline" {...props}></Icon>
