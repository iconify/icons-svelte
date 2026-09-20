<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/s/sb8bzcbcd.css';
import '../../css/b/b1w30acsv.css';
import '../../css/y/yl4tr1vao.css';
import '../../css/d/d7rn_gbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="sb8bzcbcd"/><path class="b1w30acsv"/><path class="yl4tr1vao"/><path clip-rule="evenodd" class="d7rn_gbhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:beyondcorp-enterprise-logo" {...props}></Icon>
