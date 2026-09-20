<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrr9c8bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrr9c8bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-sketch-filled" {...props}></Icon>
