<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aexwcm9er.css';
import '../../css/c/ccdp7c34j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aexwcm9er wm-k"/><path class="ccdp7c34j wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-left" {...props}></Icon>
