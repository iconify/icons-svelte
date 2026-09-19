<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/s/szyzabcia.css';
import '../../css/x/xs42h82yl.css';
import '../../css/r/rk6ey_39w.css';
import '../../css/g/gddoymk0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGuywqVbel"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGuywqVbel)"><path class="szyzabcia"/><path class="xs42h82yl"/><path class="rk6ey_39w"/><path class="gddoymk0q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:lang-bs" {...props}></Icon>
