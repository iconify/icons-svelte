<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tamqo7ynr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tamqo7ynr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamepad-variant" {...props}></Icon>
