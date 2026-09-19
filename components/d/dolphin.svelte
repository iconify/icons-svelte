<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg2dmo1tu.css';
import '../../css/h/hb6p0db8j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlCaPwdaD"><g class="ft5dv1b6b"><path class="rg2dmo1tu"/><circle class="hb6p0db8j"/></g></mask></defs><path mask="url(#SVGlCaPwdaD)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:dolphin" {...props}></Icon>
