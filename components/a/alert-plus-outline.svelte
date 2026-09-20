<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b85g23sbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b85g23sbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alert-plus-outline" {...props}></Icon>
