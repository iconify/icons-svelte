<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/f2ykp2y6k.css';
import '../../css/z/zxfgzy9hk.css';
import '../../css/s/s0vg7idxu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFes5IeWL"><g class="aql7dnt-u"><path class="f2ykp2y6k"/><path class="zxfgzy9hk"/><path class="s0vg7idxu"/></g></mask></defs><path mask="url(#SVGFes5IeWL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:double-bed" {...props}></Icon>
