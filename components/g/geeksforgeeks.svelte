<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqm57x-gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqm57x-gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:geeksforgeeks" {...props}></Icon>
