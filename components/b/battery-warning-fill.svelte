<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er_qiqwbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="er_qiqwbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-warning-fill" {...props}></Icon>
