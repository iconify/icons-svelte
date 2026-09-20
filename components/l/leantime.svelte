<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixt72zwcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixt72zwcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:leantime" {...props}></Icon>
