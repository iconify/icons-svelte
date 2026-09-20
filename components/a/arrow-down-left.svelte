<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr7uzqbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr7uzqbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-down-left" {...props}></Icon>
