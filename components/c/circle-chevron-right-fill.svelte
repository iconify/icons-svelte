<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb1_c-35o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb1_c-35o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevron-right-fill" {...props}></Icon>
