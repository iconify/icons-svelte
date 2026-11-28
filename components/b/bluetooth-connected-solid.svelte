<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiwn5ycja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiwn5ycja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bluetooth-connected-solid" {...props}></Icon>
