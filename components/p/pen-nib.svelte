<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq0kuqbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pq0kuqbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pen-nib" {...props}></Icon>
