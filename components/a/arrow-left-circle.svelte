<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v116ycm1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="v116ycm1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-left-circle" {...props}></Icon>
