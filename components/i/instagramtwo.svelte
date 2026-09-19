<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kha72tbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="kha72tbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:instagramtwo" {...props}></Icon>
