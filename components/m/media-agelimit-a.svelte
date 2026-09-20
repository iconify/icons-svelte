<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa-nzwwng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qa-nzwwng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-agelimit-a" {...props}></Icon>
