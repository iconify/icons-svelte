<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgd9a0b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rgd9a0b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:resizehorizontalalt" {...props}></Icon>
