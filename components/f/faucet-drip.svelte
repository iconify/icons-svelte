<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs8yq5bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="hs8yq5bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:faucet-drip" {...props}></Icon>
