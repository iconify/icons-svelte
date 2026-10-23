<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gojx-tb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gojx-tb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:camera-off" {...props}></Icon>
