<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/i4uadmb9d.css';
import '../../css/h/hxzj3yk3h.css';
import '../../css/i/ixrulac1n.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqu8QYcfM"><g class="v3_i3wktz"><path class="i4uadmb9d"/><path class="hxzj3yk3h"/><path class="ixrulac1n"/></g></mask></defs><path mask="url(#SVGqu8QYcfM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:first-aid-kit" {...props}></Icon>
