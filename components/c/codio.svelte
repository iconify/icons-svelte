<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avn5l5gls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avn5l5gls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:codio" {...props}></Icon>
