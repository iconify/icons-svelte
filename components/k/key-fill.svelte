<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmgkin9pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmgkin9pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:key-fill" {...props}></Icon>
