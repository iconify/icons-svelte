<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr4flk_qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr4flk_qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:long-up-left" {...props}></Icon>
