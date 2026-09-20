<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m51kbubxl.css';
import '../../css/e/ejnjdobnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m51kbubxl"/><path class="ejnjdobnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:phone-action-data-transfer-1-bold" {...props}></Icon>
