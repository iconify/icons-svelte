<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh005ibev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="qh005ibev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:phone-office" {...props}></Icon>
