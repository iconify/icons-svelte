<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d80swtbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d80swtbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:cellular-network-5g" {...props}></Icon>
