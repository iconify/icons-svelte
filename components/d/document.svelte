<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9gza1b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p9gza1b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:document" {...props}></Icon>
