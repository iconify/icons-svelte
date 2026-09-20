<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3--rezlz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3--rezlz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-multiple-plus" {...props}></Icon>
