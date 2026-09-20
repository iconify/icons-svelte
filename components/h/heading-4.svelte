<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lon5l2byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lon5l2byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-4" {...props}></Icon>
