<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v56e6zbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v56e6zbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:info-triangle-solid" {...props}></Icon>
