<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vximh_acq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vximh_acq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:citroen" {...props}></Icon>
