<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0v_txbuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0v_txbuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-pin-circle-fill" {...props}></Icon>
