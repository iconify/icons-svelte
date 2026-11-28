<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af0ycwbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af0ycwbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:campfire" {...props}></Icon>
