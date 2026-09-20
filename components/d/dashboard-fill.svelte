<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m802_1bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m802_1bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-fill" {...props}></Icon>
