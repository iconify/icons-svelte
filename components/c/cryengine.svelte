<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orb9p3cfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="orb9p3cfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cryengine" {...props}></Icon>
