<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv_dau1cf.css';
import '../../css/m/mwsfceayy.css';
import '../../css/v/vra1g0c1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv_dau1cf wm-k"/><path class="mwsfceayy wm-k"/><path class="vra1g0c1t wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:file-pdf" {...props}></Icon>
