<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk09bee9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk09bee9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-half-outline" {...props}></Icon>
