<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyqt_gb4g.css';
import '../../css/e/ehzexxbxn.css';
import '../../css/x/x4f46-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyqt_gb4g"/><path class="ehzexxbxn"/><path class="x4f46-b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:figma-file-bold-duotone" {...props}></Icon>
