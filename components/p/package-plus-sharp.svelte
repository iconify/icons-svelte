<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd110abrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd110abrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-plus-sharp" {...props}></Icon>
