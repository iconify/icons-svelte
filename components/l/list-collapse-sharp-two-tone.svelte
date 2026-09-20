<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp5hlb-sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp5hlb-sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-collapse-sharp-two-tone" {...props}></Icon>
