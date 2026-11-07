<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt_-vrosd.css';
import '../../css/l/lbbxpcczj.css';
import '../../css/e/epcli-bre.css';
import '../../css/r/r7pgarbha.css';
import '../../css/e/enasjubvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt_-vrosd"/><path class="lbbxpcczj"/><path class="epcli-bre"/><path class="r7pgarbha"/><path class="enasjubvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-left-right-ellipsis-outline" {...props}></Icon>
