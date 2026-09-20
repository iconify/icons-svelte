<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn-zulx8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn-zulx8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:link-fill" {...props}></Icon>
