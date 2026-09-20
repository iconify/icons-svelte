<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-lqwjb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-lqwjb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:openbsd" {...props}></Icon>
