<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw2jt_3pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw2jt_3pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-bold-circle" {...props}></Icon>
