<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3u8k5bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="g3u8k5bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:previous" {...props}></Icon>
