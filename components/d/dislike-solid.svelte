<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmuni9p9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmuni9p9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:dislike-solid" {...props}></Icon>
