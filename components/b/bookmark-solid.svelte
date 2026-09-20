<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc-bajzvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc-bajzvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:bookmark-solid" {...props}></Icon>
