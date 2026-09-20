<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouvm6tl5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouvm6tl5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-x" {...props}></Icon>
