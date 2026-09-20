<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_evnkbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_evnkbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:picture" {...props}></Icon>
