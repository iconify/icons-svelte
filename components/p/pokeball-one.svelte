<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/haza73b9v.css';
import '../../css/k/kdo0cub5v.css';
import '../../css/y/ysimbtxlw.css';
import '../../css/p/povs420wf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvHk3GcgI"><g class="ft5dv1b6b"><path class="haza73b9v"/><circle class="kdo0cub5v"/><path class="ysimbtxlw"/><circle class="povs420wf"/></g></mask></defs><path mask="url(#SVGvHk3GcgI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pokeball-one" {...props}></Icon>
