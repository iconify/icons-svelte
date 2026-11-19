<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5eb05w5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5eb05w5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:minus-equal" {...props}></Icon>
