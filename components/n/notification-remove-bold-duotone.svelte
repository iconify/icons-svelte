<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr2f8pbje.css';
import '../../css/c/ch9w-bbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lr2f8pbje"/><path class="ch9w-bbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-remove-bold-duotone" {...props}></Icon>
