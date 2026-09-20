<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luof2w8us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luof2w8us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:git-merge-solid" {...props}></Icon>
