<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf2opmbjc.css';
import '../../css/r/r2zxf_bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qf2opmbjc"/><path class="r2zxf_bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:headset-duotone" {...props}></Icon>
