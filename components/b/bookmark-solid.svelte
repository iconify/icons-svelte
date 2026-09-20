<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gazz5ebes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gazz5ebes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bookmark-solid" {...props}></Icon>
