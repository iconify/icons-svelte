<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxvarnb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxvarnb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:office-building-remove-outline" {...props}></Icon>
