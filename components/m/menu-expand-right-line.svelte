<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejcayhhhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejcayhhhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:menu-expand-right-line" {...props}></Icon>
