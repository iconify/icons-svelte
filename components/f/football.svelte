<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn35t7a4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn35t7a4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:football" {...props}></Icon>
