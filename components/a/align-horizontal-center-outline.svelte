<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozwmi8bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozwmi8bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-horizontal-center-outline" {...props}></Icon>
