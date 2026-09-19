<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw834mbpj.css';
import '../../css/t/tbo0rsbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bw834mbpj"/><path class="tbo0rsbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:document-text-sharp" {...props}></Icon>
