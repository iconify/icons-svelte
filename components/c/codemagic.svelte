<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5b82-uli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5b82-uli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codemagic" {...props}></Icon>
