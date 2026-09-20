<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzfrftnrw.css';
import '../../css/c/c11vxbbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qzfrftnrw"/><path clip-rule="evenodd" class="c11vxbbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:phonecall-blocked-solid" {...props}></Icon>
