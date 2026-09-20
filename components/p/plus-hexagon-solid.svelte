<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h12sh9boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h12sh9boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plus-hexagon-solid" {...props}></Icon>
