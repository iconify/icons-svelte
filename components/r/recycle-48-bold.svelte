<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otb2xbb3k.css';
import '../../css/p/pkdwskbpr.css';
import '../../css/g/g1mzogb6g.css';
import '../../css/d/da0i6bcpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="otb2xbb3k"/><path class="pkdwskbpr"/><path class="g1mzogb6g"/><path class="da0i6bcpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:recycle-48-bold" {...props}></Icon>
