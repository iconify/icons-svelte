<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic3wg7_sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="ic3wg7_sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloudaltupload" {...props}></Icon>
