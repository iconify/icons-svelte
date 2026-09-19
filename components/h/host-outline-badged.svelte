<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glggx6o7t.css';
import '../../css/s/sj_1l9bqr.css';
import '../../css/l/lmf0ecbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="glggx6o7t"/><path class="sj_1l9bqr"/><circle class="lmf0ecbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:host-outline-badged" {...props}></Icon>
