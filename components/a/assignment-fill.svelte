<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njc-z_btr.css';
import '../../css/k/kiohhd3cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njc-z_btr"/><path clip-rule="evenodd" class="kiohhd3cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:assignment-fill" {...props}></Icon>
