<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezt2hxb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezt2hxb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:forbid-line" {...props}></Icon>
