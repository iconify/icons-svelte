<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3kjyubpd.css';
import '../../css/i/i67ob3bwq.css';
import '../../css/e/esgx7hbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3kjyubpd"/><path clip-rule="evenodd" class="i67ob3bwq"/><path class="esgx7hbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-edit-1-filled" {...props}></Icon>
