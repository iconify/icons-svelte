<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh4o6tbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":700};
const content = `<path class="qh4o6tbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:check" {...props}></Icon>
