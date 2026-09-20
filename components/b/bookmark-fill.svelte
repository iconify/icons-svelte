<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx6wbyhzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx6wbyhzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:bookmark-fill" {...props}></Icon>
