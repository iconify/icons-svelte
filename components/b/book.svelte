<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uau_pxbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uau_pxbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:book" {...props}></Icon>
