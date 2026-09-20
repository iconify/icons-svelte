<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc_o6xbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc_o6xbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bereal" {...props}></Icon>
