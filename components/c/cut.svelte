<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul3dyo2bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul3dyo2bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cut" {...props}></Icon>
