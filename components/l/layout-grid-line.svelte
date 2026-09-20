<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxbp-8bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxbp-8bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-grid-line" {...props}></Icon>
