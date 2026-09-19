<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhokkbbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhokkbbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:document-chart-bar" {...props}></Icon>
