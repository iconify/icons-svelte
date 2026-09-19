<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft31dgr8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft31dgr8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-undo-down-left" {...props}></Icon>
