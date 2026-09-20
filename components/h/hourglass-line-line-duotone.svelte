<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l5ireaban.css';
import '../../css/s/sm_z9gbwi.css';
import '../../css/j/jipvxn5py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l5ireaban"/><path class="sm_z9gbwi"/><path class="jipvxn5py"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hourglass-line-line-duotone" {...props}></Icon>
