<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyzm1ebos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyzm1ebos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:a-arrow-up-filled" {...props}></Icon>
