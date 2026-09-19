<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzh7glb6r.css';
import '../../css/t/tg242fbea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="zzh7glb6r"/><path class="tg242fbea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:landscape" {...props}></Icon>
