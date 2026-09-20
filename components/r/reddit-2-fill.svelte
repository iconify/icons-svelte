<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfxaz2nik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfxaz2nik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reddit-2-fill" {...props}></Icon>
