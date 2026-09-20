<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jia3v4fcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jia3v4fcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:heading" {...props}></Icon>
