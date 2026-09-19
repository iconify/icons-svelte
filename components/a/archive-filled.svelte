<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl_7r6bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl_7r6bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:archive-filled" {...props}></Icon>
