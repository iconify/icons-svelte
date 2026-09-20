<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2xnpxb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h2xnpxb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:comb-and-scissors" {...props}></Icon>
