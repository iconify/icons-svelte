<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa6m-3b-n.css';
import '../../css/t/tszhuobqh.css';
import '../../css/z/zjx5z9b7a.css';
import '../../css/r/rzgmi4b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa6m-3b-n"/><path class="tszhuobqh"/><path class="zjx5z9b7a"/><path class="rzgmi4b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:google-play" {...props}></Icon>
