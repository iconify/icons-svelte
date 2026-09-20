<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfvac11yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfvac11yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frames-light" {...props}></Icon>
