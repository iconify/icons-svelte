<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm5l_ww-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm5l_ww-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-compare" {...props}></Icon>
