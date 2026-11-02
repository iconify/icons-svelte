<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg90zxbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg90zxbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-wide-narrow-line" {...props}></Icon>
