<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/styzegblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="styzegblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:border-top-solid" {...props}></Icon>
