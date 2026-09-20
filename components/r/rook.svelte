<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/posn_435t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="posn_435t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rook" {...props}></Icon>
