<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyghm0w-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyghm0w-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:pause-circle-outline" {...props}></Icon>
