<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5hhk_blw.css';
import '../../css/x/x03n-xhgu.css';
import '../../css/v/v67m5-lov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5hhk_blw"/><path class="x03n-xhgu"/><path class="v67m5-lov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bithumb" {...props}></Icon>
