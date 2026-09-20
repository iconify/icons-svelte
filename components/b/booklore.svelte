<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkr2s5b1k.css';
import '../../css/c/c54521b1r.css';
import '../../css/a/as_-b_2sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="lkr2s5b1k"/><path class="c54521b1r"/><path class="as_-b_2sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:booklore" {...props}></Icon>
