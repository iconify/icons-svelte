<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfdzy9bat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfdzy9bat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-panda-solid" {...props}></Icon>
