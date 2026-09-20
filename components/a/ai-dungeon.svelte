<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oopk6j_9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oopk6j_9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ai-dungeon" {...props}></Icon>
