<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af2k9-byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af2k9-byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openlayers" {...props}></Icon>
