<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcl2hxb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tcl2hxb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:heart-rate-outline" {...props}></Icon>
