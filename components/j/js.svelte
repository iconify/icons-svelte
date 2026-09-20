<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da7zqbe4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="da7zqbe4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:js" {...props}></Icon>
