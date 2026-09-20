<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pot4xccpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pot4xccpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-rain-wind" {...props}></Icon>
