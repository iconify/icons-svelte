<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbvjs_2tm.css';
import '../../css/s/s_phngbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbvjs_2tm"/><path class="s_phngbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:electricplug" {...props}></Icon>
