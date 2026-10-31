<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdg7vccce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xdg7vccce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:circle-solid" {...props}></Icon>
