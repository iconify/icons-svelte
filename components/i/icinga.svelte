<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aowv02_fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aowv02_fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:icinga" {...props}></Icon>
