<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8vzhhcat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8vzhhcat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-fog" {...props}></Icon>
