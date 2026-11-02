<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfyk8p-da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfyk8p-da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ins-line" {...props}></Icon>
