<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkpxsvb_g.css';
import '../../css/o/ot6g9xx6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gkpxsvb_g"/><path class="ot6g9xx6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:chat-line-square" {...props}></Icon>
