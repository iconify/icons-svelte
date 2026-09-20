<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guhhauoca.css';
import '../../css/p/py4wsctwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guhhauoca"/><path class="py4wsctwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-circle-left" {...props}></Icon>
