<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6k3adcvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6k3adcvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-snow-solid" {...props}></Icon>
