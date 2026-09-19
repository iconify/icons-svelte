<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqwdqgmwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqwdqgmwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:plug" {...props}></Icon>
