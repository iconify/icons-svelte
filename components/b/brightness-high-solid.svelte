<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o56yifc7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o56yifc7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brightness-high-solid" {...props}></Icon>
