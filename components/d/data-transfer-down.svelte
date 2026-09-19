<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhc-ifv-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhc-ifv-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:data-transfer-down" {...props}></Icon>
