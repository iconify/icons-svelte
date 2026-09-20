<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb8yt5fzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qb8yt5fzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libretranslate-light" {...props}></Icon>
