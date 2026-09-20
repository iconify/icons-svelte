<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7kta2eie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s7kta2eie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hotel-laundry-solid" {...props}></Icon>
