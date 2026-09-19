<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukw4jy4tx.css';
import '../../css/s/sgoebkv5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukw4jy4tx"/><path class="sgoebkv5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-right-square-half" {...props}></Icon>
