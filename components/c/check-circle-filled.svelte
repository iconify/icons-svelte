<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2r8wgrvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t2r8wgrvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:check-circle-filled" {...props}></Icon>
