<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwwvjobsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cwwvjobsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:orange-circle" {...props}></Icon>
