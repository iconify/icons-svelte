<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guv8gacua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guv8gacua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:letter-p" {...props}></Icon>
