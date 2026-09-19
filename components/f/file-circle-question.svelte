<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/douh-p_jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="douh-p_jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-circle-question" {...props}></Icon>
