<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciwn85vpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ciwn85vpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:drink" {...props}></Icon>
