<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_bbh3b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_bbh3b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:playstation-vita" {...props}></Icon>
