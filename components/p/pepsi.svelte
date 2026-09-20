<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvviu06qs.css';
import '../../css/w/wc7y-bc1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvviu06qs"/><path class="wc7y-bc1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:pepsi" {...props}></Icon>
