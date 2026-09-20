<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqx0khpxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqx0khpxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:corner-left-up" {...props}></Icon>
