<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjy8cko8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjy8cko8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:phone-off-fill" {...props}></Icon>
