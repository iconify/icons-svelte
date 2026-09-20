<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4dk4o63l.css';
import '../../css/r/rit0h486c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4dk4o63l"/><path class="rit0h486c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:phone-cancel-fill" {...props}></Icon>
