<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpi3234uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mpi3234uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:font-size-two" {...props}></Icon>
