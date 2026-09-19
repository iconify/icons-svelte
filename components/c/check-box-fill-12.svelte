<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3sd78bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="c3sd78bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-box-fill-12" {...props}></Icon>
