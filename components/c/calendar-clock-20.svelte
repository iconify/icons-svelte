<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zain2eb2r.css';
import '../../css/s/sk4ad7b3f.css';
import '../../css/e/epmi80zpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zain2eb2r"/><path class="sk4ad7b3f"/><path class="epmi80zpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-clock-20" {...props}></Icon>
