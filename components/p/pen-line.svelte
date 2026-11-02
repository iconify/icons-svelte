<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngcpec5mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngcpec5mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-line" {...props}></Icon>
