<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z486k_bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z486k_bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lemon-2-filled" {...props}></Icon>
