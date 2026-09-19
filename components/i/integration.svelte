<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xukg1wjzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xukg1wjzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:integration" {...props}></Icon>
