<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz13hwonu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kz13hwonu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mouse-alt-filled" {...props}></Icon>
