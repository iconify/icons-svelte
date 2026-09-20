<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfp4l5uux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfp4l5uux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-exchange-2" {...props}></Icon>
