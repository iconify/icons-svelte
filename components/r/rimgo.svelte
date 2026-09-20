<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4aqbt3rt.css';
import '../../css/b/beyjpfbcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k4aqbt3rt"/><circle class="beyjpfbcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rimgo" {...props}></Icon>
