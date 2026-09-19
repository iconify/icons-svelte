<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdg70bbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdg70bbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:archive-box-arrow-down" {...props}></Icon>
