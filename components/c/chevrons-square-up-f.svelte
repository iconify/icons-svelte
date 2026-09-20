<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkt65s91b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="nkt65s91b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-square-up-f" {...props}></Icon>
