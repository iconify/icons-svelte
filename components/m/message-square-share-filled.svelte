<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqu28rbuo.css';
import '../../css/k/kbmh56tfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqu28rbuo"/><path class="kbmh56tfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-share-filled" {...props}></Icon>
