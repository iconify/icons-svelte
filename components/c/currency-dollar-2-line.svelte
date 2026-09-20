<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqf_41-ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqf_41-ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-dollar-2-line" {...props}></Icon>
