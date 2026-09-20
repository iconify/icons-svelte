<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuzch45me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cuzch45me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:check-waves-solid" {...props}></Icon>
