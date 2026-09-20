<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hua0ulbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hua0ulbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:move-diagonal-one" {...props}></Icon>
