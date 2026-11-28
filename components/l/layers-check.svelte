<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikxmvscfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikxmvscfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:layers-check" {...props}></Icon>
