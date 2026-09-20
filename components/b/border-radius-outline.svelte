<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwo0tkb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kwo0tkb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-radius-outline" {...props}></Icon>
