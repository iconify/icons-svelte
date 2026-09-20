<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix48izb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ix48izb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:layout-window-1-solid" {...props}></Icon>
