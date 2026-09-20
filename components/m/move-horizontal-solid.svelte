<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyrvkswcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyrvkswcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:move-horizontal-solid" {...props}></Icon>
