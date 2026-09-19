<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4evc5b5u.css';
import '../../css/t/tmkh_-28d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p4evc5b5u"/><path class="tmkh_-28d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:moon-night" {...props}></Icon>
