<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-7n0sjuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-7n0sjuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:navigation" {...props}></Icon>
