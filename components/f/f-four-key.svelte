<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/b/bcdfr0bxx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGr6swMbc"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="bcdfr0bxx"/></g></mask></defs><path mask="url(#SVGGr6swMbc)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:f-four-key" {...props}></Icon>
