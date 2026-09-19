<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qofievr1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qofievr1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hammer-and-anvil" {...props}></Icon>
