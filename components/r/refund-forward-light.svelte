<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzdv-6b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzdv-6b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:refund-forward-light" {...props}></Icon>
