<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr2f8pbje.css';
import '../../css/x/xjq0yvb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr2f8pbje"/><path class="xjq0yvb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-remove-bold" {...props}></Icon>
