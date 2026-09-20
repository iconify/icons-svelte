<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-oq9ebpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-oq9ebpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-3-line" {...props}></Icon>
