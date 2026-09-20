<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0cenz3yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h0cenz3yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:facebook-square" {...props}></Icon>
