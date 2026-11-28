<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytzz9x6wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytzz9x6wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cooking-pot-solid" {...props}></Icon>
