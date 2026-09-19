<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6geo1bkk.css';
import '../../css/t/t_6ep1b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h6geo1bkk"/><path class="t_6ep1b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:add-comment" {...props}></Icon>
