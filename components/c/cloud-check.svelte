<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k18qk85-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k18qk85-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cloud-check" {...props}></Icon>
