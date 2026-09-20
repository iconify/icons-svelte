<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y62kftt6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y62kftt6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:power-button" {...props}></Icon>
