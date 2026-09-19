<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvy_q-q5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvy_q-q5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-three-quarter-alt-filled" {...props}></Icon>
