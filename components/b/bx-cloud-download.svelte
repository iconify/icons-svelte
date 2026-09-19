<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se_exubjd.css';
import '../../css/c/cdr84abnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se_exubjd"/><path class="cdr84abnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-cloud-download" {...props}></Icon>
