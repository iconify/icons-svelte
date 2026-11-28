<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm06f1b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm06f1b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-minus-solid" {...props}></Icon>
