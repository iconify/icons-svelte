<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci9vmlb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci9vmlb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-add-line" {...props}></Icon>
