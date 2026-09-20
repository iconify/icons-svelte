<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwyah0bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwyah0bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-pie-one" {...props}></Icon>
