<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q12o9iblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q12o9iblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hotel-search" {...props}></Icon>
