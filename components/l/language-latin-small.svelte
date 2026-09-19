<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twi6k7b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="twi6k7b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-latin-small" {...props}></Icon>
