<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1an_yugr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1an_yugr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-open" {...props}></Icon>
