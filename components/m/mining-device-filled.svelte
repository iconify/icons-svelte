<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_9hocblj.css';
import '../../css/j/jr2c_p1uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_9hocblj"/><path clip-rule="evenodd" class="jr2c_p1uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:mining-device-filled" {...props}></Icon>
