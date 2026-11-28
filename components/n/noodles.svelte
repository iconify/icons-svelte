<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl2z6zbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl2z6zbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:noodles" {...props}></Icon>
