<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm4lx_ftr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jm4lx_ftr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lock-circle-fill" {...props}></Icon>
