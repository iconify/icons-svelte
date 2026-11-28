<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6tms1bjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6tms1bjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plane-landing-solid" {...props}></Icon>
