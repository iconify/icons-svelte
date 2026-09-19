<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eddsisw-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1536};
const content = `<path class="eddsisw-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:italic" {...props}></Icon>
