<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9jgs1fzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="k9jgs1fzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hashtag" {...props}></Icon>
