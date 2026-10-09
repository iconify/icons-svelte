<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtkttskyz.css';
import '../../css/d/d1zhrdbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jtkttskyz"/><path class="d1zhrdbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flag-20-bold" {...props}></Icon>
