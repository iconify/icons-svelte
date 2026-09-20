<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m22e59wjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m22e59wjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:decap-cms" {...props}></Icon>
