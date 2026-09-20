<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsas4b2vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsas4b2vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:clock-12" {...props}></Icon>
