<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ct0bzjh.css';
import '../../css/b/bkce-3brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8ct0bzjh"/><path class="bkce-3brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:checkmark-square-outline" {...props}></Icon>
