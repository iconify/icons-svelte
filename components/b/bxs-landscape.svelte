<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzh7glb6r.css';
import '../../css/w/wnppey9ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="zzh7glb6r"/><path class="wnppey9ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-landscape" {...props}></Icon>
