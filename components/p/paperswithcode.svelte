<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9k81o5_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9k81o5_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:paperswithcode" {...props}></Icon>
