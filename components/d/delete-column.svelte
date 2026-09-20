<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y622ldbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y622ldbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-column" {...props}></Icon>
