<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea7tfxbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea7tfxbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:faucet-outline" {...props}></Icon>
