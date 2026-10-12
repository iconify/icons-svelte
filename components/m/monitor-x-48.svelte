<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9mi-m0jn.css';
import '../../css/a/azjk1obih.css';
import '../../css/k/kng-rnbst.css';
import '../../css/b/bdkl8-dne.css';
import '../../css/j/j3cy-fbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="a9mi-m0jn"/><path class="azjk1obih"/><path class="kng-rnbst"/><path class="bdkl8-dne"/><path class="j3cy-fbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:monitor-x-48" {...props}></Icon>
