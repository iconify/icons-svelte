<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzh5qzj1y.css';
import '../../css/k/knqltxb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="bzh5qzj1y"/><path class="knqltxb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:laptop-filled" {...props}></Icon>
