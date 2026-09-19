<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss1frpkay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss1frpkay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:report-columns" {...props}></Icon>
