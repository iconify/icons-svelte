<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjuc8vv5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjuc8vv5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:arrowlist" {...props}></Icon>
