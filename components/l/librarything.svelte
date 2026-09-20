<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uq-vo4ugb.css';
import '../../css/l/lhs-_ebhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uq-vo4ugb"/><path class="lhs-_ebhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librarything" {...props}></Icon>
