<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdykscxue.css';
import '../../css/s/sm0cfybmw.css';
import '../../css/e/euxfqgbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gdykscxue"/><path class="sm0cfybmw"/><path class="euxfqgbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-bolt-48" {...props}></Icon>
