<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w80w45bcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w80w45bcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:more-horizontal" {...props}></Icon>
