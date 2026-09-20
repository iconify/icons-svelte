<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-z8bpfqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-z8bpfqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:fire-line" {...props}></Icon>
