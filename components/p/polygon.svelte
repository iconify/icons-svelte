<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-ifbv4_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-ifbv4_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:polygon" {...props}></Icon>
