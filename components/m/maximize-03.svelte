<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqfn3tbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqfn3tbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:maximize-03" {...props}></Icon>
