<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7q2z9dzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":26};
const content = `<path class="i7q2z9dzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-image-26" {...props}></Icon>
