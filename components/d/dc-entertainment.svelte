<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukzk-pb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukzk-pb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dc-entertainment" {...props}></Icon>
