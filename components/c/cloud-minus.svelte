<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpbl5f9pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpbl5f9pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-minus" {...props}></Icon>
