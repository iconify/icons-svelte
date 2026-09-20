<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee09_gb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee09_gb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lamp" {...props}></Icon>
