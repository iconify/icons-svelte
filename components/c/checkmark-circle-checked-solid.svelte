<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enb9o6bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enb9o6bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:checkmark-circle-checked-solid" {...props}></Icon>
