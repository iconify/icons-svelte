<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpr-1rm3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpr-1rm3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:keyboard-solid" {...props}></Icon>
