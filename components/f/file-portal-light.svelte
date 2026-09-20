<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irsl63llt.css';
import '../../css/s/sbw6ahqto.css';
import '../../css/m/m8tny2bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="irsl63llt"/><path class="sbw6ahqto"/><path class="m8tny2bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:file-portal-light" {...props}></Icon>
