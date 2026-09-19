<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smi9hnbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smi9hnbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fork-knife" {...props}></Icon>
