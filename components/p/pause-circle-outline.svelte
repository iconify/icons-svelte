<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weq3zzqer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="weq3zzqer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pause-circle-outline" {...props}></Icon>
