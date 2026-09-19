<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md5rxcbgi.css';
import '../../css/r/rh_lsv0bg.css';
import '../../css/q/qhf2oqbcs.css';
import '../../css/m/mmdfc-b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="md5rxcbgi"/><path class="rh_lsv0bg"/><path class="qhf2oqbcs"/><path class="mmdfc-b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:beermug" {...props}></Icon>
