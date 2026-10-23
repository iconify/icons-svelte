<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olzd66nyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olzd66nyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:nepali-rupee" {...props}></Icon>
