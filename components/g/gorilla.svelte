<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw0i9f9gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw0i9f9gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:gorilla" {...props}></Icon>
