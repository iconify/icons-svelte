<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzfi-7-ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzfi-7-ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clock-3" {...props}></Icon>
