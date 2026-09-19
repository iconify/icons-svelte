<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vetpb2ele.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vetpb2ele"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:intercom" {...props}></Icon>
