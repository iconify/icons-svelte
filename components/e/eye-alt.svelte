<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0u5bhb-g.css';
import '../../css/x/x5shryb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0u5bhb-g"/><path class="x5shryb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eye-alt" {...props}></Icon>
