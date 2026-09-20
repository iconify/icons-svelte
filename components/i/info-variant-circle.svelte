<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho9g23x-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho9g23x-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:info-variant-circle" {...props}></Icon>
