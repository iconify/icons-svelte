<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2nrf10bf.css';
import '../../css/q/qzz58bb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nrf10bf"/><path clip-rule="evenodd" class="qzz58bb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-lock-bold-duotone" {...props}></Icon>
