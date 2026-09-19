<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvpaucbgz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGE5LEqc1m"><path class="lvpaucbgz"/></mask></defs><path mask="url(#SVGE5LEqc1m)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:block-two" {...props}></Icon>
