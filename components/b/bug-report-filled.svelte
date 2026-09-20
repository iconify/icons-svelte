<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_2kcdb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_2kcdb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bug-report-filled" {...props}></Icon>
