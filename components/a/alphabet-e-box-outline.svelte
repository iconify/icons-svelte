<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anfyuydls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anfyuydls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alphabet-e-box-outline" {...props}></Icon>
