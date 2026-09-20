<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa_fyp89y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa_fyp89y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-miniprogram-filled" {...props}></Icon>
