<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig6wtnb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig6wtnb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:chemex" {...props}></Icon>
