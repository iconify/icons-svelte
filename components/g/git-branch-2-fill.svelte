<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg9jf2aku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg9jf2aku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-2-fill" {...props}></Icon>
