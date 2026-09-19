<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kswr0cbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kswr0cbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-plus-filled" {...props}></Icon>
