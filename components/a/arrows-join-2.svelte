<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/ly74rvd1w.css';
import '../../css/o/ois9ejb5c.css';
import '../../css/v/vwdfj7brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ly74rvd1w"/><path class="ois9ejb5c"/><path class="vwdfj7brr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-join-2" {...props}></Icon>
