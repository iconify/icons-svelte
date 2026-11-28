<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9_hp6odt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f9_hp6odt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:petri-dish" {...props}></Icon>
