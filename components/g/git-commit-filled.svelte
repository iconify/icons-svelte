<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpkkrabjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpkkrabjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:git-commit-filled" {...props}></Icon>
