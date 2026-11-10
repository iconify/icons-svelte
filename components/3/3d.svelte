<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aktw6zwky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aktw6zwky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:3d" {...props}></Icon>
