<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o95zvjb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o95zvjb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:percentage-circle-solid" {...props}></Icon>
