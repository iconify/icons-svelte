<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd322u6xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd322u6xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:namespace" {...props}></Icon>
