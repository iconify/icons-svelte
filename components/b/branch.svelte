<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe7iz5bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe7iz5bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:branch" {...props}></Icon>
