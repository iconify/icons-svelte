<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9_tcobxs.css';
import '../../css/t/t_qou-ite.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9_tcobxs"/><path class="t_qou-ite"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bookmark-alt-minus" {...props}></Icon>
