<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myplm-wqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="myplm-wqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:battery-75-20-solid" {...props}></Icon>
