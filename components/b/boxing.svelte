<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/d/du_1q6b0d.css';
import '../../css/k/kdreqsbkh.css';
import '../../css/l/lq78wnbxw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTKh2sexh"><g class="hv130ab-t"><path class="du_1q6b0d"/><path class="kdreqsbkh"/><path class="lq78wnbxw"/></g></mask></defs><path mask="url(#SVGTKh2sexh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:boxing" {...props}></Icon>
