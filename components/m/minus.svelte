<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhy83-btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":614};
const content = `<path class="uhy83-btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:minus" {...props}></Icon>
