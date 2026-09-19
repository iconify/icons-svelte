<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9ai3q1cw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIRubIbDG"><path class="q9ai3q1cw"/></mask></defs><path mask="url(#SVGIRubIbDG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-five" {...props}></Icon>
