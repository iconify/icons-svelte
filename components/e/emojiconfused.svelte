<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj_5nup2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mj_5nup2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emojiconfused" {...props}></Icon>
