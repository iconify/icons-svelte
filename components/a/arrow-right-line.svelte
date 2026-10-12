<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc07mobmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc07mobmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-right-line" {...props}></Icon>
