<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qur8xabfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qur8xabfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:delta-filled" {...props}></Icon>
