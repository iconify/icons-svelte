<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knj52s_nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knj52s_nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-right-fill" {...props}></Icon>
