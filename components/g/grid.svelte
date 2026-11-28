<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arl6jtbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arl6jtbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:grid" {...props}></Icon>
