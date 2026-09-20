<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpejmeb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpejmeb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:git-branch-filled" {...props}></Icon>
