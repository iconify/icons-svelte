<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm2q14o2t.css';
import '../../css/c/czb5--bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qm2q14o2t"/><path class="czb5--bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:contao" {...props}></Icon>
