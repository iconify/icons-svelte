<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgpwz3b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgpwz3b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:chef-hat-star" {...props}></Icon>
