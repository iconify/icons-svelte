<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_phe1i7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y_phe1i7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:peak-demand-20" {...props}></Icon>
