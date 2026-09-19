<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6vskqo0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f6vskqo0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:decline" {...props}></Icon>
