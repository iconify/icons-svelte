<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da3mhqb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":374,"height":512};
const content = `<path class="da3mhqb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openvms" {...props}></Icon>
