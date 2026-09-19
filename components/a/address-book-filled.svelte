<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px8cn61kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px8cn61kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:address-book-filled" {...props}></Icon>
