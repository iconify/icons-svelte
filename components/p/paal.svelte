<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmd9_ci0l.css';
import '../../css/v/vv1m_xbuq.css';
import '../../css/g/gv-p15bpi.css';
import '../../css/l/lwb5uprkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmd9_ci0l"/><path class="vv1m_xbuq"/><path clip-rule="evenodd" class="gv-p15bpi"/><path class="lwb5uprkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:paal" {...props}></Icon>
