<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc3n9gn7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc3n9gn7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-dashed-linear" {...props}></Icon>
