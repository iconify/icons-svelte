<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4dwnsz2l.css';
import '../../css/y/yg151vbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4dwnsz2l"/><path clip-rule="evenodd" class="yg151vbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-cog-filled" {...props}></Icon>
