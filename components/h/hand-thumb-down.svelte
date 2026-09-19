<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9anfdc5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9anfdc5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hand-thumb-down" {...props}></Icon>
