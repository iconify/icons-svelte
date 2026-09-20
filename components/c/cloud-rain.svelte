<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcfdvlbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcfdvlbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-rain" {...props}></Icon>
