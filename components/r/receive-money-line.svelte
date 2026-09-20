<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djtj93bbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djtj93bbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:receive-money-line" {...props}></Icon>
