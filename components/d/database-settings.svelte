<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8ots_bdl.css';
import '../../css/w/w1qg11bis.css';
import '../../css/e/ehgylhzlx.css';
import '../../css/p/pkebo2bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8ots_bdl"/><path class="w1qg11bis"/><path clip-rule="evenodd" class="ehgylhzlx"/><path clip-rule="evenodd" class="pkebo2bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:database-settings" {...props}></Icon>
