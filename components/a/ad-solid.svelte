<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj80fbt_q.css';
import '../../css/t/t_1qkzbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj80fbt_q"/><path class="t_1qkzbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:ad-solid" {...props}></Icon>
