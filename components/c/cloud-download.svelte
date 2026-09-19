<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmy77ob3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmy77ob3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:cloud-download" {...props}></Icon>
