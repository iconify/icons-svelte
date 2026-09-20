<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4nz665xn.css';
import '../../css/b/b6dmwqarl.css';
import '../../css/b/bwdyegfbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a4nz665xn"/><path class="b6dmwqarl"/><path class="bwdyegfbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:marp-dark" {...props}></Icon>
