<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yft_2jb0w.css';
import '../../css/t/t476j_etv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yft_2jb0w"/><path class="t476j_etv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:copy-check-filled" {...props}></Icon>
