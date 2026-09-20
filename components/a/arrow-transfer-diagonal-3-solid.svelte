<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj3fw5t9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gj3fw5t9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-transfer-diagonal-3-solid" {...props}></Icon>
