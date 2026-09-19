<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/m/mie1pybna.css';
import '../../css/w/wyu1zabwh.css';
import '../../css/v/v5bv_7bmi.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGt2xF6gip"><g class="ufeehvblu"><path class="mie1pybna"/><path class="wyu1zabwh"/><path class="v5bv_7bmi"/></g></mask></defs><path mask="url(#SVGt2xF6gip)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:parking" {...props}></Icon>
