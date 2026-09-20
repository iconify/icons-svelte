<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qditl--gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qditl--gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:contactless-payment" {...props}></Icon>
