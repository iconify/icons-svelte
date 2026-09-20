<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkp9akf4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkp9akf4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:refund-back" {...props}></Icon>
