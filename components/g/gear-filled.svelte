<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv-robcde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tv-robcde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gear-filled" {...props}></Icon>
