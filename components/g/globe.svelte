<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob2n04b5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ob2n04b5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:globe" {...props}></Icon>
