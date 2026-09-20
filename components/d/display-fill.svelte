<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcftk1tjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcftk1tjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:display-fill" {...props}></Icon>
