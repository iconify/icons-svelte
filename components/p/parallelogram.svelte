<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obqvyrbyx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1L9OFezd"><path class="obqvyrbyx"/></mask></defs><path mask="url(#SVG1L9OFezd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:parallelogram" {...props}></Icon>
