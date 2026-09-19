<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daapk0d1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daapk0d1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:list-ul-square-filled" {...props}></Icon>
