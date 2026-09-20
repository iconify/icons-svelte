<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcb9oqsfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcb9oqsfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:night-moon-half-1-bold" {...props}></Icon>
