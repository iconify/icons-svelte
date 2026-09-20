<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqwxb2_1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lqwxb2_1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-remix" {...props}></Icon>
