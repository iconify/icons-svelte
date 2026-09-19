<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljc5zc_ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="ljc5zc_ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:publons" {...props}></Icon>
