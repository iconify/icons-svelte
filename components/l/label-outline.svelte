<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjfeavyrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjfeavyrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:label-outline" {...props}></Icon>
