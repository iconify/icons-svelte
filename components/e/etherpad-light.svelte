<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5biwmbup.css';
import '../../css/g/gjgzt7bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5biwmbup"/><path class="gjgzt7bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etherpad-light" {...props}></Icon>
