<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr6jcd5ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vr6jcd5ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-alert" {...props}></Icon>
