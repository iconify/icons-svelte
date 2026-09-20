<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q62gep4ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="q62gep4ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-network" {...props}></Icon>
