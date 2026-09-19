<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-um4sufk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-um4sufk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-2-light" {...props}></Icon>
