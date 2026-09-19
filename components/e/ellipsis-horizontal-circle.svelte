<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilp8-kwbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilp8-kwbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:ellipsis-horizontal-circle" {...props}></Icon>
