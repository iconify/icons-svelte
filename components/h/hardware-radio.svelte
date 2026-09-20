<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9j36gb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9j36gb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:hardware-radio" {...props}></Icon>
