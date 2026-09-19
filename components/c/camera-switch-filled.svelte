<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6kt_2byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6kt_2byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-switch-filled" {...props}></Icon>
