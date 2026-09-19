<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j53nm-bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j53nm-bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:magnifying-glass-minus" {...props}></Icon>
