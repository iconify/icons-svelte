<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8ved5nop.css';
import '../../css/s/s5d7qab8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8ved5nop"/><path class="s5d7qab8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-star" {...props}></Icon>
