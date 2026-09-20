<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_jweoq5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_jweoq5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chevron-right-filled" {...props}></Icon>
