<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz7jt4b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz7jt4b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:podium-star" {...props}></Icon>
