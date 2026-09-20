<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd-nkug3f.css';
import '../../css/c/cqcsowpco.css';
import '../../css/e/e2doa554v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bd-nkug3f"/><path class="cqcsowpco"/><path class="e2doa554v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:registry-console-light" {...props}></Icon>
