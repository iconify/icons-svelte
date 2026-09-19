<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfedqwb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfedqwb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bookmark" {...props}></Icon>
