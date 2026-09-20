<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8xe44b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-3.5};
const content = `<path class="u8xe44b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:brightness-down-f" {...props}></Icon>
