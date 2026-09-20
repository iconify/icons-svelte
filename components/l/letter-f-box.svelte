<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfvpqvbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfvpqvbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:letter-f-box" {...props}></Icon>
