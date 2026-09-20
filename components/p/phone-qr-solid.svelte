<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb06wxbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kb06wxbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-qr-solid" {...props}></Icon>
