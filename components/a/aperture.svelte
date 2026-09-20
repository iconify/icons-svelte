<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6n6vn4qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6n6vn4qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:aperture" {...props}></Icon>
