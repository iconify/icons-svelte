<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czzhmhbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czzhmhbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-circle-down-left-filled" {...props}></Icon>
