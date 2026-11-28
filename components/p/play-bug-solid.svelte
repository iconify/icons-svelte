<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffybyabpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffybyabpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:play-bug-solid" {...props}></Icon>
