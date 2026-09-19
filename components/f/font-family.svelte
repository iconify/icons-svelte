<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj0bk4b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj0bk4b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:font-family" {...props}></Icon>
