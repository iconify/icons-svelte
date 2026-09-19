<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/n31vb0b7j.css';
import '../../css/x/xi0idpw6x.css';
import '../../css/n/nyqrc9mhu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlchFtdVg"><g class="v3_i3wktz"><path class="n31vb0b7j"/><path class="xi0idpw6x"/><path class="nyqrc9mhu"/></g></mask></defs><path mask="url(#SVGlchFtdVg)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:key" {...props}></Icon>
