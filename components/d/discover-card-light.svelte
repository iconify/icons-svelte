<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0yozqbdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0yozqbdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:discover-card-light" {...props}></Icon>
