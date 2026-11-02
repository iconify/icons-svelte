<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx2h1bb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx2h1bb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paragraph-fill" {...props}></Icon>
