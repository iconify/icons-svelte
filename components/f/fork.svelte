<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jypf_8bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="jypf_8bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:fork" {...props}></Icon>
