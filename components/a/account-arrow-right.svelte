<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlwazgaoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlwazgaoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-arrow-right" {...props}></Icon>
