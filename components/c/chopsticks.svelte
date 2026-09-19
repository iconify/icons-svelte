<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzs1ir2gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzs1ir2gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chopsticks" {...props}></Icon>
