<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9jjl7gyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9jjl7gyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:grid-alt" {...props}></Icon>
