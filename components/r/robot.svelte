<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvbjpfbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvbjpfbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:robot" {...props}></Icon>
