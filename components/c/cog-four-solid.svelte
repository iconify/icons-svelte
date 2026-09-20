<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge-76lk_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ge-76lk_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cog-four-solid" {...props}></Icon>
