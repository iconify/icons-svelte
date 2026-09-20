<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehdcugbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehdcugbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:beer-off" {...props}></Icon>
