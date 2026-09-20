<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b383qj07c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b383qj07c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:align-right" {...props}></Icon>
