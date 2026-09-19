<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ig4v93e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ig4v93e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pen-line" {...props}></Icon>
