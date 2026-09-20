<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um71q_bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um71q_bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:cut" {...props}></Icon>
