<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_to3pbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_to3pbxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-docs" {...props}></Icon>
