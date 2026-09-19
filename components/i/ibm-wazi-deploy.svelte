<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6na-zfmx.css';
import '../../css/e/evd4z-yaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i6na-zfmx"/><path class="evd4z-yaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-wazi-deploy" {...props}></Icon>
