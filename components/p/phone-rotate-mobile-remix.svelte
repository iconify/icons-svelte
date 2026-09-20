<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygs9l0b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ygs9l0b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:phone-rotate-mobile-remix" {...props}></Icon>
