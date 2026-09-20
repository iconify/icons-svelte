<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajrs5fbzp.css';
import '../../css/h/hkgap18lv.css';
import '../../css/t/t_aewkbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ajrs5fbzp"/><path class="hkgap18lv"/><path class="t_aewkbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-grids-dark" {...props}></Icon>
