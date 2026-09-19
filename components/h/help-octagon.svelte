<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbcy3hzsq.css';
import '../../css/l/lwa5up2ml.css';
import '../../css/r/rw27qob_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbcy3hzsq"/><path class="lwa5up2ml"/><path class="rw27qob_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:help-octagon" {...props}></Icon>
