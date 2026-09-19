<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjw4yqthe.css';
import '../../css/y/ylop8ebio.css';
import '../../css/s/s0fwv-0ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjw4yqthe"/><path class="ylop8ebio"/><path class="s0fwv-0ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:gke-on-prem" {...props}></Icon>
