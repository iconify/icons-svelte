<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/haza73b9v.css';
import '../../css/r/r58jvyboq.css';
import '../../css/y/ysimbtxlw.css';
import '../../css/q/qznx_nb7p.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeX6CWdHQ"><g class="ft5dv1b6b"><path class="haza73b9v"/><circle class="r58jvyboq"/><path class="ysimbtxlw"/><circle class="qznx_nb7p"/></g></mask></defs><path mask="url(#SVGeX6CWdHQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:pokeball-one" {...props}></Icon>
