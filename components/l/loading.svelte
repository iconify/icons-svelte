<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znl267sqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znl267sqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:loading" {...props}></Icon>
