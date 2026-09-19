<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iryic-bvb.css';
import '../../css/a/a0ra-m2wj.css';
import '../../css/m/m_uixnbmd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtPctNetI"><g class="ft5dv1b6b"><path class="iryic-bvb"/><path class="a0ra-m2wj"/><path clip-rule="evenodd" class="m_uixnbmd"/></g></mask></defs><path mask="url(#SVGtPctNetI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:helpcenter" {...props}></Icon>
