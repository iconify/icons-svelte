<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n95qa7blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n95qa7blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:alt" {...props}></Icon>
