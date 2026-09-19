<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idh4sbcyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="idh4sbcyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:green-circle" {...props}></Icon>
