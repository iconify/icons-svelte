<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr_t7240v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr_t7240v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:circle-7" {...props}></Icon>
