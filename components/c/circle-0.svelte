<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1lkf0bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1lkf0bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:circle-0" {...props}></Icon>
