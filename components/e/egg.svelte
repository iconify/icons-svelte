<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvp3xeyyy.css';
import '../../css/m/ml87_nbsm.css';
import '../../css/r/r9sv3-ufk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="uvp3xeyyy"/><circle class="ml87_nbsm"/><path class="r9sv3-ufk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:egg" {...props}></Icon>
