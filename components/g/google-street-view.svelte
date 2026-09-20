<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cek597b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cek597b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-street-view" {...props}></Icon>
