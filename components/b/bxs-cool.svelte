<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bstr61-li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bstr61-li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cool" {...props}></Icon>
