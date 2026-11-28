<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1913d5an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1913d5an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:piggy-bank" {...props}></Icon>
