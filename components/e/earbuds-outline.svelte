<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5igpwbax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5igpwbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:earbuds-outline" {...props}></Icon>
