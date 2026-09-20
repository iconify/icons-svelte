<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lppfvri4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lppfvri4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:list-number" {...props}></Icon>
