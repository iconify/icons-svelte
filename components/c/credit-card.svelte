<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upbpp921n.css';
import '../../css/k/k-g2zcgtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upbpp921n"/><path class="k-g2zcgtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:credit-card" {...props}></Icon>
