<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfe1kszww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfe1kszww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:forward" {...props}></Icon>
