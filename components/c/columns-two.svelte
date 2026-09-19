<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp5nucc6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp5nucc6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:columns-two" {...props}></Icon>
