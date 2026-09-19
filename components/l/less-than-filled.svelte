<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy063fhvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy063fhvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:less-than-filled" {...props}></Icon>
