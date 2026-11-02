<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw6p4ccxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw6p4ccxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-send-fill" {...props}></Icon>
