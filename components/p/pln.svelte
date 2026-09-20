<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgfp4e6dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgfp4e6dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pln" {...props}></Icon>
