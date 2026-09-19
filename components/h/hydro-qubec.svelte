<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osqbz69em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osqbz69em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hydro-qubec" {...props}></Icon>
