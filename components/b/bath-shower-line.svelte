<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku0o0cc0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku0o0cc0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:bath-shower-line" {...props}></Icon>
