<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdm-cibjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdm-cibjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:paper-plane" {...props}></Icon>
