<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi49eh3za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pi49eh3za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:bright-button" {...props}></Icon>
