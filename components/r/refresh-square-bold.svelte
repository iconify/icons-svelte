<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cih8fbbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cih8fbbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:refresh-square-bold" {...props}></Icon>
