<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-zj_7vyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-zj_7vyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:droplet" {...props}></Icon>
