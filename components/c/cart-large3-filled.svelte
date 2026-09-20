<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prqma6b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prqma6b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cart-large3-filled" {...props}></Icon>
