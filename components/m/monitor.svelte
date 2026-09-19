<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd-1kf17z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd-1kf17z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:monitor" {...props}></Icon>
