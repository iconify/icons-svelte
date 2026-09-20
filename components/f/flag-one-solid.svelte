<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6f1htxrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6f1htxrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:flag-one-solid" {...props}></Icon>
