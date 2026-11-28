<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ei2acct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i2ei2acct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:clock-plus-thin" {...props}></Icon>
