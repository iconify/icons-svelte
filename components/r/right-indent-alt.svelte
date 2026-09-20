<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzs_ybc9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzs_ybc9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:right-indent-alt" {...props}></Icon>
