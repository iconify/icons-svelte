<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qplp73bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qplp73bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-alert" {...props}></Icon>
