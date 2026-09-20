<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny3teufhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ny3teufhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:file-bookmark-solid" {...props}></Icon>
