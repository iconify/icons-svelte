<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0at0g3bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0at0g3bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:key" {...props}></Icon>
