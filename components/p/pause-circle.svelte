<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2d7dbc9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2d7dbc9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:pause-circle" {...props}></Icon>
