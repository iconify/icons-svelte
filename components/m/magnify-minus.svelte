<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skiszgg3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="skiszgg3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:magnify-minus" {...props}></Icon>
