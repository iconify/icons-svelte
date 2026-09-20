<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfyep0bnp.css';
import '../../css/a/a8ubjjxwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cfyep0bnp"/><path class="a8ubjjxwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:mobile-phone" {...props}></Icon>
