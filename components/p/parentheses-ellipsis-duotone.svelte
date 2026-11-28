<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkkt6hb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vkkt6hb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:parentheses-ellipsis-duotone" {...props}></Icon>
