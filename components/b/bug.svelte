<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/brkrw9h7x.css';
import '../../css/t/ty_pvobpe.css';
import '../../css/y/y7js8hemd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrMDBveSg"><g class="v3_i3wktz"><path class="brkrw9h7x"/><path class="ty_pvobpe"/><path class="y7js8hemd"/></g></mask></defs><path mask="url(#SVGrMDBveSg)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:bug" {...props}></Icon>
