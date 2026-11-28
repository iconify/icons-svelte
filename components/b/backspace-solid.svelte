<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0my4wugx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0my4wugx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:backspace-solid" {...props}></Icon>
