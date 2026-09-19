<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu410db3i.css';
import '../../css/v/voo8clboo.css';
import '../../css/l/lmf0ecbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="mu410db3i"/><path class="voo8clboo"/><circle class="lmf0ecbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:control-lun-solid-badged" {...props}></Icon>
