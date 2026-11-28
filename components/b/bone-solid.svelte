<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9tw53b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9tw53b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bone-solid" {...props}></Icon>
