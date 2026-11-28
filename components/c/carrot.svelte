<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv2a0ygbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv2a0ygbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:carrot" {...props}></Icon>
