<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpeq1mbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpeq1mbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-lightning-filled" {...props}></Icon>
