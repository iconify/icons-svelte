<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3eu34blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3eu34blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:component" {...props}></Icon>
