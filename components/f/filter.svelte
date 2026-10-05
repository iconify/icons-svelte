<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2uh3nw7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2uh3nw7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:filter" {...props}></Icon>
