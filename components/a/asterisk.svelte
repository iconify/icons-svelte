<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkt2k58qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mkt2k58qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:asterisk" {...props}></Icon>
