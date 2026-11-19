<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbf85eblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbf85eblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:absolute-value" {...props}></Icon>
