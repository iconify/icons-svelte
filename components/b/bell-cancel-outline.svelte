<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpi3gdb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpi3gdb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-cancel-outline" {...props}></Icon>
