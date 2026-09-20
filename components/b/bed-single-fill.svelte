<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv52_k8xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv52_k8xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bed-single-fill" {...props}></Icon>
