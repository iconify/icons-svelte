<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w36ucgumf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w36ucgumf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:arrow-circle-down" {...props}></Icon>
