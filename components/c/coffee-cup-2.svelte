<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9rsasb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9rsasb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:coffee-cup-2" {...props}></Icon>
