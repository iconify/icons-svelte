<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnxkxebxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="bnxkxebxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillenine" {...props}></Icon>
