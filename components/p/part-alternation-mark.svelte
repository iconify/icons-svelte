<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz7v9cbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cz7v9cbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:part-alternation-mark" {...props}></Icon>
