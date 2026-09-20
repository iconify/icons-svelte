<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0ennjy9f.css';
import '../../css/a/a446ljbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ennjy9f"/><path clip-rule="evenodd" class="a446ljbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:drag-squares-horizontal-duotone" {...props}></Icon>
