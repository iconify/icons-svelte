<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilz_7jali.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ilz_7jali"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hourglass-bottomhalf-fill" {...props}></Icon>
