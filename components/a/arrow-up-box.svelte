<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxuajgb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxuajgb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-up-box" {...props}></Icon>
