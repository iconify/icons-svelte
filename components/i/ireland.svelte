<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9cl-boot.css';
import '../../css/r/rltssxbuj.css';
import '../../css/g/g323dnkch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="l9cl-boot"/><path class="rltssxbuj"/><path class="g323dnkch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:ireland" {...props}></Icon>
