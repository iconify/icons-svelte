<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsbzt18rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wsbzt18rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-pound-20-solid" {...props}></Icon>
