<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrdvcwidb.css';
import '../../css/u/ug-4vnsfs.css';
import '../../css/w/we0hyhblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="ug-4vnsfs"/><path class="we0hyhblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quote-circle-bold-duotone" {...props}></Icon>
