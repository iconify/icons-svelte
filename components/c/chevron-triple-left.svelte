<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuf2nkvgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuf2nkvgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-triple-left" {...props}></Icon>
