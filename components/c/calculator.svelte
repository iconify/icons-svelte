<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofk05cbfv.css';
import '../../css/p/p7hyuf70f.css';
import '../../css/j/j8mjksuyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ofk05cbfv"/><path class="p7hyuf70f"/><path class="j8mjksuyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:calculator" {...props}></Icon>
