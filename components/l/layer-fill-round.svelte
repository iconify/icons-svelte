<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgojwzbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgojwzbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layer-fill-round" {...props}></Icon>
