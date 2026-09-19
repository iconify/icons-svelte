<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/f694ycdso.css';
import '../../css/z/z3m924b_g.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcZLgRdnM"><g class="v3_i3wktz"><path class="f694ycdso"/><path class="z3m924b_g"/></g></mask></defs><path mask="url(#SVGcZLgRdnM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:expand-left" {...props}></Icon>
