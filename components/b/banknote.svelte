<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft7lyubfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft7lyubfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:banknote" {...props}></Icon>
