<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2u665ban.css';
import '../../css/s/szel5gblr.css';
import '../../css/g/gb-hbngty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="szel5gblr"/><path class="gb-hbngty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:new-folder" {...props}></Icon>
