<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz43omb9k.css';
import '../../css/h/hsrg7muou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz43omb9k"/><path clip-rule="evenodd" class="hsrg7muou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:like-bold-duotone" {...props}></Icon>
