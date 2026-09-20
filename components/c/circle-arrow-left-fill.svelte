<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzri7tbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kzri7tbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-left-fill" {...props}></Icon>
