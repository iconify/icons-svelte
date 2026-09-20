<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjt82jqis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjt82jqis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-left-circle-solid" {...props}></Icon>
