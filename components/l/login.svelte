<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmpf8o31a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kmpf8o31a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:login" {...props}></Icon>
