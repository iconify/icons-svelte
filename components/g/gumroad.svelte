<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fer9r4bph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fer9r4bph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gumroad" {...props}></Icon>
