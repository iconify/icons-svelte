<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehjtzrcbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehjtzrcbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-plus-solid" {...props}></Icon>
