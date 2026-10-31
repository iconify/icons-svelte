<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9cl-boot.css';
import '../../css/v/v4iotl68y.css';
import '../../css/t/t2w8mls_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="l9cl-boot"/><path class="v4iotl68y"/><path class="t2w8mls_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:france" {...props}></Icon>
