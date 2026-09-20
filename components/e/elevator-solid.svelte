<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqun_gwda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqun_gwda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:elevator-solid" {...props}></Icon>
