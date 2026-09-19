<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkc4yf0kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkc4yf0kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:peacock" {...props}></Icon>
