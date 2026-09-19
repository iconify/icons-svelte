<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_rjmbc4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_rjmbc4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:import" {...props}></Icon>
