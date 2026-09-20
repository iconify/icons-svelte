<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixfou5b7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixfou5b7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:animal-products-egg-bold" {...props}></Icon>
