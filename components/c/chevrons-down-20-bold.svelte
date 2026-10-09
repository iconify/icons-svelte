<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj-p4p_9x.css';
import '../../css/u/uavtgqbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kj-p4p_9x"/><path class="uavtgqbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-down-20-bold" {...props}></Icon>
