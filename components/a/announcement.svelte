<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/y36p79bsk.css';
import '../../css/s/sj4ws-i4j.css';
import '../../css/a/a4m4flg4d.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGghnIveXz"><g class="v3_i3wktz"><rect class="y36p79bsk"/><path class="sj4ws-i4j"/><path class="a4m4flg4d"/></g></mask></defs><path mask="url(#SVGghnIveXz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:announcement" {...props}></Icon>
