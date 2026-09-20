<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykwmyg3xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykwmyg3xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:message-plus-fill" {...props}></Icon>
