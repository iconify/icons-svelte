<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_04yvq2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="z_04yvq2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-circle-down-right-f" {...props}></Icon>
