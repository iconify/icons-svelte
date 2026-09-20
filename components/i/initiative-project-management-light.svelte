<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1q08elin.css';
import '../../css/l/lqso_0biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r1q08elin"/><path class="lqso_0biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:initiative-project-management-light" {...props}></Icon>
