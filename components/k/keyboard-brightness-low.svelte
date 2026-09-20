<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjjeli3sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjjeli3sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:keyboard-brightness-low" {...props}></Icon>
