<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aepzuabco.css';
import '../../css/g/gqgo7nzta.css';
import '../../css/v/vv-f_hbum.css';
import '../../css/k/knae6-b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aepzuabco"/><path class="gqgo7nzta"/><path class="vv-f_hbum"/><path class="knae6-b4y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:doge" {...props}></Icon>
