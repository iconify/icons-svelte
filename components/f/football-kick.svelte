<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuxwwovsb.css';
import '../../css/b/b6hnulsaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuxwwovsb"/><path class="b6hnulsaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:football-kick" {...props}></Icon>
