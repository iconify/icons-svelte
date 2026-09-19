<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qe0g46bxg.css';
import '../../css/e/euxi43hbo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWVRuoepI"><g class="v3_i3wktz"><path class="qe0g46bxg"/><path class="euxi43hbo"/></g></mask></defs><path mask="url(#SVGWVRuoepI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:phone-call" {...props}></Icon>
