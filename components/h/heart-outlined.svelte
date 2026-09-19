<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxqbb4wdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kxqbb4wdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:heart-outlined" {...props}></Icon>
