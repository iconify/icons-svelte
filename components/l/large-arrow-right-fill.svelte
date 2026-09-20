<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj00wcbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zj00wcbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:large-arrow-right-fill" {...props}></Icon>
