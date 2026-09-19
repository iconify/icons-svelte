<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erx1m70kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erx1m70kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cloud" {...props}></Icon>
