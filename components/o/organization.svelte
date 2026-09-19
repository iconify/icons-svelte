<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8lp5cx1a.css';
import '../../css/m/m4237cc8k.css';
import '../../css/r/r654q-uhd.css';
import '../../css/t/thhi6b9md.css';
import '../../css/m/msio13ifn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8lp5cx1a"/><circle class="m4237cc8k"/><circle class="r654q-uhd"/><circle class="thhi6b9md"/><circle class="msio13ifn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:organization" {...props}></Icon>
