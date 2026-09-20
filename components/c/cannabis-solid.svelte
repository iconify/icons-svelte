<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s92f2jh7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s92f2jh7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cannabis-solid" {...props}></Icon>
