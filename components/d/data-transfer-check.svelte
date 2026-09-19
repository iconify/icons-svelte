<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np27zabkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np27zabkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:data-transfer-check" {...props}></Icon>
