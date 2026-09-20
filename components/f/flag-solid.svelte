<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eam_kubxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eam_kubxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:flag-solid" {...props}></Icon>
