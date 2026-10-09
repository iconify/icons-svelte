<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4crdmbww.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/r/r5d58utxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j4crdmbww"/><path class="hwjgqrbah"/><path class="r5d58utxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-check-48-bold" {...props}></Icon>
