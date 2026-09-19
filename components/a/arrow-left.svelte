<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgs7_xe4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgs7_xe4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:arrow-left" {...props}></Icon>
