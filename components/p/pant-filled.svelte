<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crfylpbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crfylpbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pant-filled" {...props}></Icon>
