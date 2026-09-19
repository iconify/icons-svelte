<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktp18214b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ktp18214b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:low-vision-24px" {...props}></Icon>
