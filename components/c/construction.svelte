<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb_zv80mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nb_zv80mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:construction" {...props}></Icon>
