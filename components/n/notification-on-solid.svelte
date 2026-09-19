<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyrkcgbkt.css';
import '../../css/p/pkjpf3lqg.css';
import '../../css/a/a-g2__2wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyrkcgbkt"/><path clip-rule="evenodd" class="pkjpf3lqg"/><path class="a-g2__2wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:notification-on-solid" {...props}></Icon>
