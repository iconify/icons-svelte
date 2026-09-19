<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/d6a9rordt.css';
import '../../css/h/hizj3i7nm.css';
import '../../css/l/lfuwnosgt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYFnZib2o"><g class="v3_i3wktz"><rect class="d6a9rordt"/><path class="hizj3i7nm"/><path class="lfuwnosgt"/></g></mask></defs><path mask="url(#SVGYFnZib2o)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:boiler" {...props}></Icon>
