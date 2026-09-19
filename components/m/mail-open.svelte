<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/hihlctbwv.css';
import '../../css/h/hvzd0ubol.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGz8UWde7M"><g class="v3_i3wktz"><path class="hihlctbwv"/><path class="hvzd0ubol"/></g></mask></defs><path mask="url(#SVGz8UWde7M)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:mail-open" {...props}></Icon>
