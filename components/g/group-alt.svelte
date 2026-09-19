<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz-p99uxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lz-p99uxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:group-alt" {...props}></Icon>
