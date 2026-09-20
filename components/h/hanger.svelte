<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfex-6f3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfex-6f3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:hanger" {...props}></Icon>
