<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0qviobds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0qviobds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:dice-4" {...props}></Icon>
