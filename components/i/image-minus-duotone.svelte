<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz8c3l5-w.css';
import '../../css/k/kel-qrbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz8c3l5-w"/><path class="kel-qrbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-minus-duotone" {...props}></Icon>
