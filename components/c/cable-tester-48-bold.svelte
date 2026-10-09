<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pifoudbdm.css';
import '../../css/v/vuyyv1qil.css';
import '../../css/v/vr8_6rk9r.css';
import '../../css/l/lggnzh-ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pifoudbdm"/><path class="vuyyv1qil"/><path class="vr8_6rk9r"/><path class="lggnzh-ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-tester-48-bold" {...props}></Icon>
