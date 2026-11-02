<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whz2j_bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whz2j_bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-baht-2-fill" {...props}></Icon>
