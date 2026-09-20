<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smrup5bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smrup5bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:picture-in-picture-sharp" {...props}></Icon>
