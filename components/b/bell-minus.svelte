<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig_amlb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig_amlb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bell-minus" {...props}></Icon>
