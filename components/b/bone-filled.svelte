<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lludr_bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lludr_bts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bone-filled" {...props}></Icon>
