<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf863cbsv.css';
import '../../css/z/zfmuiycex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nf863cbsv"/><path class="zfmuiycex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-up-bold-duotone" {...props}></Icon>
