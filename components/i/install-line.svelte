<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmdsglb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmdsglb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:install-line" {...props}></Icon>
