<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt10cwbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="vt10cwbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fx" {...props}></Icon>
