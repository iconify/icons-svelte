<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n13jb9w1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n13jb9w1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:nfc" {...props}></Icon>
