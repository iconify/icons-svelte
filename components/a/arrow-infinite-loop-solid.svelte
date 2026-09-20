<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksr3zxbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ksr3zxbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-infinite-loop-solid" {...props}></Icon>
