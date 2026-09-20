<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg82h9bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg82h9bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:framer" {...props}></Icon>
