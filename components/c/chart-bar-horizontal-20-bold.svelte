<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iztj1m4kj.css';
import '../../css/m/mr6auulay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iztj1m4kj"/><path class="mr6auulay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-bar-horizontal-20-bold" {...props}></Icon>
