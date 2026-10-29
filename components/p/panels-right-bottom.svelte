<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gesw5mb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gesw5mb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panels-right-bottom" {...props}></Icon>
