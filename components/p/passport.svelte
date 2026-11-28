<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7q6un40l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v7q6un40l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:passport" {...props}></Icon>
