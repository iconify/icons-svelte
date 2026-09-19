<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wypti6afj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wypti6afj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:battery" {...props}></Icon>
