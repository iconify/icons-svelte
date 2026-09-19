<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opmr5m07o.css';
import '../../css/c/c5qcubb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opmr5m07o"/><path class="c5qcubb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-right-square-filled" {...props}></Icon>
