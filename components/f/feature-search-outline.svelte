<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm6vyv7bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm6vyv7bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:feature-search-outline" {...props}></Icon>
