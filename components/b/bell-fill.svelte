<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly_6v1tzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly_6v1tzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:bell-fill" {...props}></Icon>
