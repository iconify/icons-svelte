<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu56ovb5t.css';
import '../../css/x/x8f5lbcvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu56ovb5t"/><path class="x8f5lbcvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:lock-square-fill" {...props}></Icon>
