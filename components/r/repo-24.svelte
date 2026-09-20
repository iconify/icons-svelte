<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diaqm204w.css';
import '../../css/j/juknf3fay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="diaqm204w"/><path class="juknf3fay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-24" {...props}></Icon>
