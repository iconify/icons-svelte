<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpqk98bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpqk98bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:raindrops-alt-filled" {...props}></Icon>
