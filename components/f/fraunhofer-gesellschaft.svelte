<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwiq2935u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwiq2935u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fraunhofer-gesellschaft" {...props}></Icon>
