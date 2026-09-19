<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiyr-ntec.css';
import '../../css/w/wp8qz4bad.css';
import '../../css/b/bqapg30rg.css';
import '../../css/h/hny4-63og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kiyr-ntec"/><path class="wp8qz4bad"/><path class="bqapg30rg"/><path class="hny4-63og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:qr-code" {...props}></Icon>
