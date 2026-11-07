<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcs6tehmj.css';
import '../../css/m/ml1bsrb5l.css';
import '../../css/f/fsv_d9evq.css';
import '../../css/d/dkkib-ewx.css';
import '../../css/v/ve8higxbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kcs6tehmj"/><path class="ml1bsrb5l"/><path class="fsv_d9evq"/><path class="dkkib-ewx"/><path class="ve8higxbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reel-2-outline" {...props}></Icon>
