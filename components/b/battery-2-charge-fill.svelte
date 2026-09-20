<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp4c2mbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp4c2mbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:battery-2-charge-fill" {...props}></Icon>
