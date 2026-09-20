<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6a025wpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-3};
const content = `<path class="d6a025wpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:beer" {...props}></Icon>
