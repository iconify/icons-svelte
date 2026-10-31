<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msfe23xvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msfe23xvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-arrow-left-round" {...props}></Icon>
