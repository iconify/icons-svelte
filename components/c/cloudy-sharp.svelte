<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sew8kkscr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sew8kkscr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cloudy-sharp" {...props}></Icon>
