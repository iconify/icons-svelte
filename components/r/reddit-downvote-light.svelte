<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et91lnbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="et91lnbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reddit-downvote-light" {...props}></Icon>
