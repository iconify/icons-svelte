<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf_cs6bdq.css';
import '../../css/k/kyh3gn_rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf_cs6bdq"/><path class="kyh3gn_rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pipe-duotone" {...props}></Icon>
