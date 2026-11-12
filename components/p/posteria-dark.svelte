<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1e8thrft.css';
import '../../css/v/v_shcmxcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1e8thrft"/><path class="v_shcmxcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:posteria-dark" {...props}></Icon>
