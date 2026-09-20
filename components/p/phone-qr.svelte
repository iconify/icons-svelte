<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naapkv9xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="naapkv9xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-qr" {...props}></Icon>
