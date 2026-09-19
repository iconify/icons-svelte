<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-9hypb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-9hypb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bike" {...props}></Icon>
