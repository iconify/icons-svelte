<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7m6bdb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7m6bdb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:metro" {...props}></Icon>
