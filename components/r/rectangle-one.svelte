<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac_q7z1tz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYs6MwejR"><path class="ac_q7z1tz"/></mask></defs><path mask="url(#SVGYs6MwejR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rectangle-one" {...props}></Icon>
