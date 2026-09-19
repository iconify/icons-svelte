<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot-y1i3we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot-y1i3we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-circle-up-filled" {...props}></Icon>
