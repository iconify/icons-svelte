<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvldghopo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvldghopo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:palo-alto-software" {...props}></Icon>
