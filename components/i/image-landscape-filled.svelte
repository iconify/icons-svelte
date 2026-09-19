<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk_r7tbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk_r7tbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-landscape-filled" {...props}></Icon>
