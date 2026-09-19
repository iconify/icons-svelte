<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-ff7xbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v-ff7xbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:open-book" {...props}></Icon>
