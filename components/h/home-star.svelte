<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppj3bmbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppj3bmbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home-star" {...props}></Icon>
