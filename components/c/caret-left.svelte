<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doch_vycb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doch_vycb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:caret-left" {...props}></Icon>
