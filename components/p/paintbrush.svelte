<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzz6dhkzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzz6dhkzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:paintbrush" {...props}></Icon>
