<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbv8r5b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dbv8r5b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:address-book-filled" {...props}></Icon>
