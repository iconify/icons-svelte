<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p42mq7fqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p42mq7fqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:record-mail-line" {...props}></Icon>
