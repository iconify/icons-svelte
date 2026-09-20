<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7h7v2bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7h7v2bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:facebook-messenger" {...props}></Icon>
