<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-icjnfkk.css';
import '../../css/p/pslrgkb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-icjnfkk"/><path class="pslrgkb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deepinfra" {...props}></Icon>
