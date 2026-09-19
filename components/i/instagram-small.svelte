<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/als9jgl4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="als9jgl4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:instagram-small" {...props}></Icon>
