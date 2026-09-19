<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccucf8nmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccucf8nmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pin-slash-alt" {...props}></Icon>
