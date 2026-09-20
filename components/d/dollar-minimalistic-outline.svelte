<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh2o2ku1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nh2o2ku1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dollar-minimalistic-outline" {...props}></Icon>
