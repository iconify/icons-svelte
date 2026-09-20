<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8tw9h6bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8tw9h6bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:crosshair" {...props}></Icon>
