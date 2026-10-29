<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b38sfdbfi.css';
import '../../css/a/a6bur7awm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b38sfdbfi wm-k"/><path class="a6bur7awm wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:heart-pulse" {...props}></Icon>
