<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kei2h4l7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kei2h4l7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-none-outline" {...props}></Icon>
