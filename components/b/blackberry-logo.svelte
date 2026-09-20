<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgkclj3cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgkclj3cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:blackberry-logo" {...props}></Icon>
