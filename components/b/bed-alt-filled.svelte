<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2eqh8bvq.css';
import '../../css/o/o0t7-245s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2eqh8bvq"/><path class="o0t7-245s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bed-alt-filled" {...props}></Icon>
