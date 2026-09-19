<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzba4of-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzba4of-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:prosthetic-leg" {...props}></Icon>
