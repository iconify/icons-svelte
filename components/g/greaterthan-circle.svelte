<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj-mhdcsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lj-mhdcsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:greaterthan-circle" {...props}></Icon>
