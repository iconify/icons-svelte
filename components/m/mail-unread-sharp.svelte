<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4cmerb_j.css';
import '../../css/d/d8hhl9rhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c4cmerb_j"/><path class="d8hhl9rhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mail-unread-sharp" {...props}></Icon>
