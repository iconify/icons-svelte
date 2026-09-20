<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxljpd16z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qxljpd16z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:keyhole-lock-circle-solid" {...props}></Icon>
