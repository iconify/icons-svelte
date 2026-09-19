<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gasgx252x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gasgx252x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:price-cut" {...props}></Icon>
