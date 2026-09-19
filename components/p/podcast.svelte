<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_sovfbpg.css';
import '../../css/e/ebu29qyhz.css';
import '../../css/u/u7krydeao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_sovfbpg"/><path class="ebu29qyhz"/><path class="u7krydeao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:podcast" {...props}></Icon>
