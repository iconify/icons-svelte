<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qns_s2bni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qns_s2bni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:function-filled" {...props}></Icon>
