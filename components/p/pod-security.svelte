<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrfp4-bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrfp4-bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:pod-security" {...props}></Icon>
