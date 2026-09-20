<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsq404tth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nsq404tth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pin-20-solid" {...props}></Icon>
