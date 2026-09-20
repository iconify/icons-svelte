<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw_cqjble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw_cqjble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-44-small" {...props}></Icon>
