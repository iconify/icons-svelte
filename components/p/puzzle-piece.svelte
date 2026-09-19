<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiyqsjbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="fiyqsjbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:puzzle-piece" {...props}></Icon>
