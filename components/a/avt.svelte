<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1l45ccjy.css';
import '../../css/b/b-5uoz78u.css';
import '../../css/a/a4yfnabqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1l45ccjy"/><path class="b-5uoz78u"/><path class="a4yfnabqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:avt" {...props}></Icon>
