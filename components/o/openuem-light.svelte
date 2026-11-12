<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h568fcbae.css';
import '../../css/x/x1ipfizhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="h568fcbae"/><path class="x1ipfizhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openuem-light" {...props}></Icon>
