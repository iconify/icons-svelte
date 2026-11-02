<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orzj4k13d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orzj4k13d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-plus-fill" {...props}></Icon>
