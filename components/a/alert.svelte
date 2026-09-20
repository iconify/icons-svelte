<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shdo169pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="shdo169pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:alert" {...props}></Icon>
