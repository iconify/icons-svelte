<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd1x97zzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd1x97zzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:calendar-detail-filled" {...props}></Icon>
