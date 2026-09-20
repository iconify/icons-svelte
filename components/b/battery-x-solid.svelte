<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt9ie6bek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt9ie6bek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:battery-x-solid" {...props}></Icon>
