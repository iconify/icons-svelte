<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c39_9dbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c39_9dbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:home" {...props}></Icon>
