<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_2newb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="i_2newb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-left-long-expressive" {...props}></Icon>
