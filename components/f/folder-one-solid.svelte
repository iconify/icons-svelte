<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upts52bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upts52bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-one-solid" {...props}></Icon>
