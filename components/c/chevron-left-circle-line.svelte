<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlhblnjsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlhblnjsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-left-circle-line" {...props}></Icon>
