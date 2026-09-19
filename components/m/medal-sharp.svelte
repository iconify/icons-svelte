<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjy_8-bky.css';
import '../../css/y/yehn7qb3c.css';
import '../../css/x/xfs19bcvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gjy_8-bky"/><path class="yehn7qb3c"/><circle class="xfs19bcvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:medal-sharp" {...props}></Icon>
