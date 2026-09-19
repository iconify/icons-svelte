<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ev9z3v0zw.css';
import '../../css/t/t8r88gqxo.css';
import '../../css/a/akb4v_5vd.css';
import '../../css/d/dm9cfkb6z.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJKHj5dcm"><g class="ft5dv1b6b"><rect class="ev9z3v0zw"/><path class="t8r88gqxo"/><circle class="akb4v_5vd"/><circle class="dm9cfkb6z"/></g></mask></defs><path mask="url(#SVGJKHj5dcm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:category-management" {...props}></Icon>
