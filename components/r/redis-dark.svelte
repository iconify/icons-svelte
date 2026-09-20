<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8ypn-bbu.css';
import '../../css/a/a4a1azmng.css';
import '../../css/c/cbtgv-02r.css';
import '../../css/p/puamdebye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t8ypn-bbu"/><path class="a4a1azmng"/><path class="cbtgv-02r"/><path class="puamdebye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redis-dark" {...props}></Icon>
