<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm4hurb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm4hurb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:check-bold" {...props}></Icon>
