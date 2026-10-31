<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rztg2463w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rztg2463w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:lettered-list" {...props}></Icon>
