<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtm_ikbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xtm_ikbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:clear-fill" {...props}></Icon>
