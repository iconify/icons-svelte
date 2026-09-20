<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi3ef9muv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pi3ef9muv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diploma-outline" {...props}></Icon>
