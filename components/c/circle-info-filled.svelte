<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgq8rcbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgq8rcbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-info-filled" {...props}></Icon>
