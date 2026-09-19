<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w54qbjugd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w54qbjugd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:purse" {...props}></Icon>
