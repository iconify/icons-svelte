<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4kw_lbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4kw_lbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-start" {...props}></Icon>
