<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8vo07bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8vo07bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bell-plus" {...props}></Icon>
