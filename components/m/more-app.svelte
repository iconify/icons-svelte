<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/ynfcuo-wb.css';
import '../../css/e/e_7i-ix1w.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGX9MiJeJu"><g class="v3_i3wktz"><path class="ynfcuo-wb"/><path class="e_7i-ix1w"/></g></mask></defs><path mask="url(#SVGX9MiJeJu)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:more-app" {...props}></Icon>
