<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg-3l4cle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wg-3l4cle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-rotate2-filled" {...props}></Icon>
