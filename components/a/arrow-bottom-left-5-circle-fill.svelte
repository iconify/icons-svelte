<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouxk6zp2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ouxk6zp2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-bottom-left-5-circle-fill" {...props}></Icon>
