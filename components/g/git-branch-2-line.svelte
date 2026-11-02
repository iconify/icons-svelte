<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lka0l_80a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lka0l_80a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-2-line" {...props}></Icon>
