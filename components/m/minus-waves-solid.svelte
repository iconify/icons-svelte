<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvgy__y-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvgy__y-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:minus-waves-solid" {...props}></Icon>
