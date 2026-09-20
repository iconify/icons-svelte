<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4esp7b2q.css';
import '../../css/i/im-69xmjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u4esp7b2q"/><path class="im-69xmjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:feeds-fun-dark" {...props}></Icon>
