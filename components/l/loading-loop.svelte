<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqogua.css';
import '../../css/t/tr-2c6-rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqogua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:loading-loop" {...props}></Icon>
