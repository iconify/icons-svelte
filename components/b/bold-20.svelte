<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5fb9gbyc.css';
import '../../css/m/mpi65j14y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i5fb9gbyc"/><path class="mpi65j14y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bold-20" {...props}></Icon>
