<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1v2eibcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r1v2eibcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:projector-screen-fill" {...props}></Icon>
