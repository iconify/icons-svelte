<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3xl0p8yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3xl0p8yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heart-line" {...props}></Icon>
