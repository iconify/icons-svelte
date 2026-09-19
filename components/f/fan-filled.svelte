<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfnyw7bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfnyw7bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fan-filled" {...props}></Icon>
