<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnll1ccis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnll1ccis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:check-square" {...props}></Icon>
