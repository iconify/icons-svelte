<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7c84o2ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n7c84o2ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emojisorry" {...props}></Icon>
