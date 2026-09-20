<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd9m6dbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd9m6dbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bullet-point" {...props}></Icon>
