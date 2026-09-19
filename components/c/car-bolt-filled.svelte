<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5cr_nptn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5cr_nptn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:car-bolt-filled" {...props}></Icon>
