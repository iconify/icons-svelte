<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6d97fbdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6d97fbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-circle-plus-filled" {...props}></Icon>
