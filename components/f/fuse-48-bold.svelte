<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfno_j3ae.css';
import '../../css/w/w-p1obhec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sfno_j3ae"/><path class="w-p1obhec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuse-48-bold" {...props}></Icon>
