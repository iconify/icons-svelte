<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivn4hmzox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivn4hmzox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ox" {...props}></Icon>
