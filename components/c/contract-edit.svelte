<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhha2ndkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhha2ndkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:contract-edit" {...props}></Icon>
