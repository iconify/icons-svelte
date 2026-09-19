<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq_72vemr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dq_72vemr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-cloud-circle" {...props}></Icon>
